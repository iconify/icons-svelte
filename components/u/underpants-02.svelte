<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6embgs7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6embgs7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:underpants-02" {...props}></Icon>
