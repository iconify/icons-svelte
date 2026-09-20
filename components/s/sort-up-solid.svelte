<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q63--4k9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q63--4k9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sort-up-solid" {...props}></Icon>
