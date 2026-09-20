<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya863lksw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya863lksw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:twitter-logo-2" {...props}></Icon>
