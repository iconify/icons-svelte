<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty867ghkp.css';
import '../../css/q/qwjuf14gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty867ghkp"/><path clip-rule="evenodd" class="qwjuf14gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-minus-outline" {...props}></Icon>
