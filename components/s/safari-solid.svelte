<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy3n31i7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cy3n31i7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:safari-solid" {...props}></Icon>
