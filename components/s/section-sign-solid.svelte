<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4rz78bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v4rz78bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:section-sign-solid" {...props}></Icon>
