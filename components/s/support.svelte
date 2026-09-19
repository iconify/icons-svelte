<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3yq5d6rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3yq5d6rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:support" {...props}></Icon>
