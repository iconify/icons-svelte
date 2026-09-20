<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuw3jibtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kuw3jibtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vector-bezier-3-fill" {...props}></Icon>
