<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojad3gbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ojad3gbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:trello-logo-solid" {...props}></Icon>
