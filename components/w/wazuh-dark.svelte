<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weij14cdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="weij14cdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wazuh-dark" {...props}></Icon>
