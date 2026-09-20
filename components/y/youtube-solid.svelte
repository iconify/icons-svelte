<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4uwgeb9s.css';
import '../../css/y/yo4ocac3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g4uwgeb9s"/><path clip-rule="evenodd" class="yo4ocac3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:youtube-solid" {...props}></Icon>
