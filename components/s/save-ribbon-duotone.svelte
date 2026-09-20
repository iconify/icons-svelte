<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iig0ngsil.css';
import '../../css/f/f3oom5dbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iig0ngsil"/><path class="f3oom5dbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:save-ribbon-duotone" {...props}></Icon>
