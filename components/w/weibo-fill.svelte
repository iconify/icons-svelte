<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdoiq_qel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdoiq_qel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:weibo-fill" {...props}></Icon>
