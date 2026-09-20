<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pubfowbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pubfowbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:yin-yang-symbol-solid" {...props}></Icon>
