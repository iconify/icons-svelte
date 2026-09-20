<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj-d1dbcu.css';
import '../../css/i/iasza6mmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj-d1dbcu"/><path class="iasza6mmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:stars-duotone" {...props}></Icon>
