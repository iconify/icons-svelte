<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci-sjkbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci-sjkbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:sun-1" {...props}></Icon>
