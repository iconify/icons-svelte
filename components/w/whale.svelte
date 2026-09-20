<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j25csyqbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j25csyqbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:whale" {...props}></Icon>
