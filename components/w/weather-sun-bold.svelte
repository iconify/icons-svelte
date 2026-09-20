<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aps518b5a.css';
import '../../css/l/l41zmqbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aps518b5a"/><path class="l41zmqbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:weather-sun-bold" {...props}></Icon>
