<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drv6t-b4e.css';
import '../../css/j/jnwm9c43p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="drv6t-b4e"/><path class="jnwm9c43p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:theta" {...props}></Icon>
