<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrevxgb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wrevxgb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:voice-mail-solid" {...props}></Icon>
