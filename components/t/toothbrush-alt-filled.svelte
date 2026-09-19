<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpm5gpbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpm5gpbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:toothbrush-alt-filled" {...props}></Icon>
