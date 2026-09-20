<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux53b_6so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ux53b_6so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:smiley-drool-solid" {...props}></Icon>
