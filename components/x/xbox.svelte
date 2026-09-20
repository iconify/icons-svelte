<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezew3_aws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezew3_aws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:xbox" {...props}></Icon>
