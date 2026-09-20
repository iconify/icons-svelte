<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwt6dac6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fwt6dac6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:trello-logo-block" {...props}></Icon>
