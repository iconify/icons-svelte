<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvc0w3uso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dvc0w3uso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:scanner-bar-code-remix" {...props}></Icon>
