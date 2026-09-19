<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvno79jxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jvno79jxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:wand-rays-inverse" {...props}></Icon>
