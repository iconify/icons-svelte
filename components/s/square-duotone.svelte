<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqjmsh66x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqjmsh66x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:square-duotone" {...props}></Icon>
