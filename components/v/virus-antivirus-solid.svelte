<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf8ooobpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qf8ooobpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:virus-antivirus-solid" {...props}></Icon>
