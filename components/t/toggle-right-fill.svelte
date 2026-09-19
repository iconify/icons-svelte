<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmur6okjy.css';
import '../../css/z/zjsfxxucc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="nmur6okjy"/><path class="zjsfxxucc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:toggle-right-fill" {...props}></Icon>
