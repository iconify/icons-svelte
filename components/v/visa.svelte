<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak21erbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="ak21erbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:visa" {...props}></Icon>
