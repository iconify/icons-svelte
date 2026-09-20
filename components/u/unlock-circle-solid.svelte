<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b90ocibzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="b90ocibzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:unlock-circle-solid" {...props}></Icon>
