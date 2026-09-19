<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2o-8kr3y.css';
import '../../css/n/nhitelbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2o-8kr3y"/><path class="nhitelbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:window-mac" {...props}></Icon>
