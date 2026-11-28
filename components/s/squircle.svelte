<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv4icwedh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv4icwedh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:squircle" {...props}></Icon>
