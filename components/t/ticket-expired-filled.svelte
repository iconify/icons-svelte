<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr9fqs4ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr9fqs4ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ticket-expired-filled" {...props}></Icon>
