<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb8k_1dbx.css';
import '../../css/k/k9ywmeb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kb8k_1dbx"/><circle class="k9ywmeb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:universal-design" {...props}></Icon>
