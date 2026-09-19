<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfkx1ubzo.css';
import '../../css/w/wq8x2ubgv.css';
import '../../css/w/wge49ob4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="cfkx1ubzo"/><circle class="wq8x2ubgv"/><path class="wge49ob4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:speaker-fill" {...props}></Icon>
