<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp5o2yxoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gp5o2yxoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:sun-min-fill" {...props}></Icon>
