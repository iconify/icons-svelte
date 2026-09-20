<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7ihtzb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7ihtzb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tallymark-1" {...props}></Icon>
