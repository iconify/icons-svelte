<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f99tpmb6q.css';
import '../../css/q/qamjhebaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f99tpmb6q"/><path class="qamjhebaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-plus-duotone" {...props}></Icon>
