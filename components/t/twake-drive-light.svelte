<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx6ko4buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jx6ko4buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:twake-drive-light" {...props}></Icon>
