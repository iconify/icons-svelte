<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whytibb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="whytibb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:text-image-center-large-remix" {...props}></Icon>
