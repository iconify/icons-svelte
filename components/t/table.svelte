<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hixq24oop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":646};
const content = `<path class="hixq24oop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:table" {...props}></Icon>
