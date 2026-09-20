<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukq-o_bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukq-o_bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:send-sharp-fill" {...props}></Icon>
