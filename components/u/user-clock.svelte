<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4zjbgbjz.css';
import '../../css/i/i7fuergcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4zjbgbjz"/><path class="i7fuergcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-clock" {...props}></Icon>
