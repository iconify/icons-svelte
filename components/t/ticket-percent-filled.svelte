<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzblx-bxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kzblx-bxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ticket-percent-filled" {...props}></Icon>
