<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7p-uactz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g7p-uactz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:tag-alt-solid" {...props}></Icon>
