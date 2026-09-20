<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwno12vfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zwno12vfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:sign-out-squre-fill" {...props}></Icon>
