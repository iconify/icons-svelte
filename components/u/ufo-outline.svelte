<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6-2od-ft.css';
import '../../css/k/kb3qv9b3z.css';
import '../../css/z/zkdww2byo.css';
import '../../css/x/xu5i9lf5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6-2od-ft"/><path class="kb3qv9b3z"/><path class="zkdww2byo"/><path class="xu5i9lf5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ufo-outline" {...props}></Icon>
