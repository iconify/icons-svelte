<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jytnoj_6w.css';
import '../../css/y/yeai0_c-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jytnoj_6w"/><path class="yeai0_c-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:volume-up-fill" {...props}></Icon>
