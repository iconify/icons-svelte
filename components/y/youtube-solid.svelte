<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moedhcbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="moedhcbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:youtube-solid" {...props}></Icon>
