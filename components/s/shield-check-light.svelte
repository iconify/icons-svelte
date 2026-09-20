<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0viuutrh.css';
import '../../css/f/fy-g4rb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0viuutrh"/><path class="fy-g4rb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:shield-check-light" {...props}></Icon>
