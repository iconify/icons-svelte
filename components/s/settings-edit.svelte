<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1ch9w2el.css';
import '../../css/n/n4n5f992h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w1ch9w2el"/><path class="n4n5f992h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:settings-edit" {...props}></Icon>
