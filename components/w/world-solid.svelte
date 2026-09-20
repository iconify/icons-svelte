<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q01kas6kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q01kas6kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:world-solid" {...props}></Icon>
