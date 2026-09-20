<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s00wh1b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s00wh1b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shield-check-filled" {...props}></Icon>
