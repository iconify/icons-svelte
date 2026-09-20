<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwzc6v6gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwzc6v6gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:super-user" {...props}></Icon>
