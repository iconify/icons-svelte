<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un9hywbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="un9hywbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:telescope-outline" {...props}></Icon>
