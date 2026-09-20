<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib9o-eblw.css';
import '../../css/k/kret6cc4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib9o-eblw"/><path class="kret6cc4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:triangle-circle-24" {...props}></Icon>
