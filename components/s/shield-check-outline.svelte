<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io5xcjbzm.css';
import '../../css/q/qwjuf14gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io5xcjbzm"/><path clip-rule="evenodd" class="qwjuf14gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-check-outline" {...props}></Icon>
