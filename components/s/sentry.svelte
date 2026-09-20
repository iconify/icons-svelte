<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq7ipe2um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq7ipe2um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sentry" {...props}></Icon>
