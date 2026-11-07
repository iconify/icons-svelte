<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmsc1wmek.css';
import '../../css/q/q1sggqbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmsc1wmek"/><path clip-rule="evenodd" class="q1sggqbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slash-circle-outline" {...props}></Icon>
