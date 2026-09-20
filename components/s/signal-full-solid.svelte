<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkljsib1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="tkljsib1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:signal-full-solid" {...props}></Icon>
