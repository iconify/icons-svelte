<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymhzve50f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ymhzve50f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-pencil-fill" {...props}></Icon>
