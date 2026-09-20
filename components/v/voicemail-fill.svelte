<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u25rjsbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u25rjsbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:voicemail-fill" {...props}></Icon>
