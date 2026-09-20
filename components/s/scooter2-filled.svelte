<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj24h4blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nj24h4blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:scooter2-filled" {...props}></Icon>
