<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-bpev3sk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-bpev3sk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:showers" {...props}></Icon>
