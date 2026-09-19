<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2lx5jb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v2lx5jb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:trash-a" {...props}></Icon>
