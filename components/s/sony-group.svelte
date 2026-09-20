<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyuwmlbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":263.352,"height":46.74};
const content = `<path class="jyuwmlbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sony-group" {...props}></Icon>
