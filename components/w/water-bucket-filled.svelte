<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt6gpltkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xt6gpltkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:water-bucket-filled" {...props}></Icon>
