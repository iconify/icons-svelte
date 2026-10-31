<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fold3jzin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fold3jzin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:slack-round" {...props}></Icon>
