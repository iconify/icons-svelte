<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-02zybhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-02zybhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:share-bold" {...props}></Icon>
