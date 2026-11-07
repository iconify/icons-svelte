<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiqdz-8ts.css';
import '../../css/q/q1sggqbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hiqdz-8ts"/><path clip-rule="evenodd" class="q1sggqbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-italic-circle-outline" {...props}></Icon>
