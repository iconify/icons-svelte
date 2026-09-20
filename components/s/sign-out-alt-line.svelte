<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnek95zaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnek95zaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:sign-out-alt-line" {...props}></Icon>
