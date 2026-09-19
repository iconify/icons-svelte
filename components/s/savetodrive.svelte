<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7sdekpfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k7sdekpfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:savetodrive" {...props}></Icon>
