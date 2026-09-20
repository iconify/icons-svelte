<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_ddf0b5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o_ddf0b5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sentry-light" {...props}></Icon>
