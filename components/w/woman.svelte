<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f91fo6bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="f91fo6bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:woman" {...props}></Icon>
