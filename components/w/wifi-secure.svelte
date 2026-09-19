<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3vyg8drj.css';
import '../../css/l/ljcvjmvwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o3vyg8drj"/><path class="ljcvjmvwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:wifi-secure" {...props}></Icon>
