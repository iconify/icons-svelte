<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxmq40l3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="hxmq40l3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:shield-minus" {...props}></Icon>
