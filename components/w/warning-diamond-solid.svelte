<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/diha6obbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="diha6obbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:warning-diamond-solid" {...props}></Icon>
