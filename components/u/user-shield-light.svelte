<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbpi54-3i.css';
import '../../css/h/h4vuonvwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbpi54-3i"/><path class="h4vuonvwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-shield-light" {...props}></Icon>
