<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbr956rgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dbr956rgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:server-environment" {...props}></Icon>
