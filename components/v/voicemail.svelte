<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/w/wt6ddqrsu.css';
import '../../css/y/yj8rovbyf.css';
import '../../css/n/nl66y9men.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="wt6ddqrsu"/><circle class="yj8rovbyf"/><path class="nl66y9men"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:voicemail" {...props}></Icon>
