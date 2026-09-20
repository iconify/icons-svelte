<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1d31hc0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1d31hc0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:thumb-up-alt-1-fill" {...props}></Icon>
