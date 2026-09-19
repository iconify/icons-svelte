<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eim6lnoap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="eim6lnoap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:sslmanager" {...props}></Icon>
