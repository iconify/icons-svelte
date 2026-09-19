<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9iko8apb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="a9iko8apb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:trash-restore-alt" {...props}></Icon>
