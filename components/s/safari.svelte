<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezijqjblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":778};
const content = `<path class="ezijqjblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:safari" {...props}></Icon>
