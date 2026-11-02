<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuw4hdc2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuw4hdc2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wechat-line" {...props}></Icon>
