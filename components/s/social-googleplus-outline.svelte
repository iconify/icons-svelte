<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4rwk7b8u.css';
import '../../css/r/r8fapn48o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m4rwk7b8u"/><path class="r8fapn48o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-googleplus-outline" {...props}></Icon>
