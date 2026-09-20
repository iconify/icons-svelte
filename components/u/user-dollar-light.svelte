<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c46s_0bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c46s_0bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-dollar-light" {...props}></Icon>
