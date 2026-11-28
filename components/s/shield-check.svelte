<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofg_qd6-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofg_qd6-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:shield-check" {...props}></Icon>
