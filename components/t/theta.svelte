<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk-c8jugz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kk-c8jugz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:theta" {...props}></Icon>
