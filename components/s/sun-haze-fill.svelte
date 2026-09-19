<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa2e7s9da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="aa2e7s9da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:sun-haze-fill" {...props}></Icon>
