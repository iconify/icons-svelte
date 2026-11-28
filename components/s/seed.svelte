<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-f6l0bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-f6l0bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:seed" {...props}></Icon>
