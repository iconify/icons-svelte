<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_bb64bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_bb64bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:users-crown" {...props}></Icon>
