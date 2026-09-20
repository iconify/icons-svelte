<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnni-et4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qnni-et4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:threat-phone-solid" {...props}></Icon>
