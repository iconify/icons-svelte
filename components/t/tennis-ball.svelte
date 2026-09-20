<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms3s0gb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms3s0gb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:tennis-ball" {...props}></Icon>
