<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4lqbstxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4lqbstxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-slash-sharp-fill" {...props}></Icon>
