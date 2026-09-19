<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmy8fnbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lmy8fnbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:sin" {...props}></Icon>
