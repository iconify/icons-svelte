<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npzehtboi.css';
import '../../css/o/o887d5btn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="npzehtboi"/><path class="o887d5btn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:suitcase-rolling-solid" {...props}></Icon>
