<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukk6o2w9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ukk6o2w9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:vlc-logo-solid" {...props}></Icon>
