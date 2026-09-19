<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqh79mb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqh79mb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:small-lamp-alt" {...props}></Icon>
