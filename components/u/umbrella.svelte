<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmno5fv-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmno5fv-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:umbrella" {...props}></Icon>
