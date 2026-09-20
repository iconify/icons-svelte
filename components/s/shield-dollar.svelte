<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px2gognml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="px2gognml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shield-dollar" {...props}></Icon>
