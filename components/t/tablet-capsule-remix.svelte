<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr34jrfns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kr34jrfns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:tablet-capsule-remix" {...props}></Icon>
