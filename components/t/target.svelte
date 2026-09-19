<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8f5sybzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f8f5sybzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:target" {...props}></Icon>
