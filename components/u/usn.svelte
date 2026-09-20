<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vunaabcms.css';
import '../../css/o/om-jm0bjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vunaabcms"/><path clip-rule="evenodd" class="om-jm0bjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:usn" {...props}></Icon>
