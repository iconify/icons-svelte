<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3w7ii3ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z3w7ii3ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-shield" {...props}></Icon>
