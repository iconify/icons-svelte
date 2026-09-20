<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_lh51auu.css';
import '../../css/n/nmf1tu78z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_lh51auu"/><path class="nmf1tu78z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-4-line" {...props}></Icon>
