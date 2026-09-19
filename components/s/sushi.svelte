<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5yw5vult.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a5yw5vult"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:sushi" {...props}></Icon>
