<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyzqo1buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hyzqo1buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:uber" {...props}></Icon>
