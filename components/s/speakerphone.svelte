<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4hnn6fqm.css';
import '../../css/i/i5cu0abur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z4hnn6fqm"/><path class="i5cu0abur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:speakerphone" {...props}></Icon>
